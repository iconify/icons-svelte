<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sny_5xbwt.css';
import '../../css/v/vfc-bbbmi.css';
import '../../css/f/flpd0t45k.css';
import '../../css/s/sn3nb_u0r.css';
import '../../css/r/rjj64pbka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="sny_5xbwt"/><path class="vfc-bbbmi"/><path class="flpd0t45k"/><path class="sn3nb_u0r"/><path class="rjj64pbka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:saint-kitts-and-nevis" {...props}></Icon>
