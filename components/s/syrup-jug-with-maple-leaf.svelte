<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk2q3ab5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lk2q3ab5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:syrup-jug-with-maple-leaf" {...props}></Icon>
