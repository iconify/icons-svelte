<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/g/ggml7abuz.css';
import '../../css/k/kd_0y5b8q.css';
import '../../css/i/i_84bmb_e.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJ6yoqbiA"><g class="v3_i3wktz"><path class="ggml7abuz"/><path class="kd_0y5b8q"/><path class="i_84bmb_e"/></g></mask></defs><path mask="url(#SVGJ6yoqbiA)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:thermometer" {...props}></Icon>
