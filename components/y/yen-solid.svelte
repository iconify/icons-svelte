<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzh7s7btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="jzh7s7btr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:yen-solid" {...props}></Icon>
