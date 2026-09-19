<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/smw8xmqtj.css';
import '../../css/l/ly3wpy45t.css';
import '../../css/z/zzopqyboz.css';
import '../../css/n/nr7gnttmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="smw8xmqtj"/><path class="ly3wpy45t"/><path class="zzopqyboz"/><path class="nr7gnttmf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tram" {...props}></Icon>
