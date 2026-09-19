<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrm_6qm5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrm_6qm5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sana-alt" {...props}></Icon>
