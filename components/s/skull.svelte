<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/e/ewcc34bhv.css';
import '../../css/k/k8mutcwuq.css';
import '../../css/v/v-2zg7byz.css';
import '../../css/s/skwuo4btv.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG6B8DTsOJ"><g class="v3_i3wktz"><path class="ewcc34bhv"/><path class="k8mutcwuq"/><path class="v-2zg7byz"/><path class="skwuo4btv"/></g></mask></defs><path mask="url(#SVG6B8DTsOJ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:skull" {...props}></Icon>
