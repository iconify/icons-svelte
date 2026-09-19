<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyk27hxcx.css';
import '../../css/l/lxvvbdcsj.css';
import '../../css/u/u90_kz3vk.css';
import '../../css/v/vsnq63-xh.css';
import '../../css/v/vzkmoxbec.css';
import '../../css/u/u81171hdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qyk27hxcx"/><path class="lxvvbdcsj"/><path class="u90_kz3vk"/><path class="vsnq63-xh"/><path class="vzkmoxbec"/><circle class="u81171hdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:smartphone-tablet" {...props}></Icon>
