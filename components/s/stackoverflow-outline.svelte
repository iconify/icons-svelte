<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh6ky0bnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lh6ky0bnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:stackoverflow-outline" {...props}></Icon>
