<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/i/i3aa71r2c.css';
import '../../css/i/i39gejnmb.css';
import '../../css/k/kg2irmbhn.css';
import '../../css/n/ngslmpbzu.css';
import '../../css/k/kj_-zqb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="i3aa71r2c wm-deco"/><path class="i39gejnmb wm-deco"/><path class="kg2irmbhn wm-k"/><path class="ngslmpbzu wm-a"/><path class="kj_-zqb7o wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:video-camera-blueprint" {...props}></Icon>
