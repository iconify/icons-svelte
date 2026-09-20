<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/q0yxk0-pj.css';
import '../../css/g/gl9qqh_kw.css';
import '../../css/z/zxxx85blj.css';
import '../../css/n/nns-klk_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="q0yxk0-pj"/><path class="gl9qqh_kw"/><path class="zxxx85blj"/><path class="nns-klk_e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:webcam-2" {...props}></Icon>
