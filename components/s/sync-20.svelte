<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-ilkisjd.css';
import '../../css/n/n-b_rl70t.css';
import '../../css/s/s8zhrbi_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f-ilkisjd"/><path class="n-b_rl70t"/><path class="s8zhrbi_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sync-20" {...props}></Icon>
