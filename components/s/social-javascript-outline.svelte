<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9kdxsbyj.css';
import '../../css/s/skl1w_bhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o9kdxsbyj"/><path class="skl1w_bhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-javascript-outline" {...props}></Icon>
