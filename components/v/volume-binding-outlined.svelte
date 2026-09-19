<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbr48rber.css';
import '../../css/n/neglx700n.css';
import '../../css/r/raaz8qbsm.css';
import '../../css/v/vueepbcbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbr48rber"/><path class="neglx700n"/><path class="raaz8qbsm"/><path class="vueepbcbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:volume-binding-outlined" {...props}></Icon>
