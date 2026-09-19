<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcc_rab_e.css';
import '../../css/b/b916efb9j.css';
import '../../css/w/w6jofhbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="kcc_rab_e"/><path class="b916efb9j"/><path class="w6jofhbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-instagram" {...props}></Icon>
