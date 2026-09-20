<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwcngf5wj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xwcngf5wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:ruby-solid" {...props}></Icon>
