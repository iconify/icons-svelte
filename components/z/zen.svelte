<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueu-zdbxw.css';
import '../../css/m/m_hk1_b6x.css';
import '../../css/g/g4uvfabpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ueu-zdbxw"/><path class="m_hk1_b6x"/><path class="g4uvfabpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:zen" {...props}></Icon>
