<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db5sjti-j.css';
import '../../css/m/mc7-3mbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="db5sjti-j"/><path class="mc7-3mbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-angular-outline" {...props}></Icon>
