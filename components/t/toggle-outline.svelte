<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjxr91cpr.css';
import '../../css/j/jq4bsyb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="pjxr91cpr"/><rect class="jq4bsyb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:toggle-outline" {...props}></Icon>
