<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwn5zdbbq.css';
import '../../css/c/csaqs8n_p.css';
import '../../css/s/sscizya7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bwn5zdbbq"/><path class="csaqs8n_p"/><path class="sscizya7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wireless-charging-48" {...props}></Icon>
