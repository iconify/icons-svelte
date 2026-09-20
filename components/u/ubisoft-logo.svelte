<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/m/m-nuw3bni.css';
import '../../css/p/pirkdkbpw.css';
import '../../css/c/cg3sp7bpj.css';
import '../../css/u/u4w82dlzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="m-nuw3bni"/><path class="pirkdkbpw"/><path class="cg3sp7bpj"/><path class="u4w82dlzp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:ubisoft-logo" {...props}></Icon>
