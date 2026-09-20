<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kra6u_baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="kra6u_baj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:skiing" {...props}></Icon>
