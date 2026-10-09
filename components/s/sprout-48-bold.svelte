<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/neebw0buz.css';
import '../../css/m/mg2rwedkj.css';
import '../../css/c/cek4p1-qj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="neebw0buz"/><path class="mg2rwedkj"/><path class="cek4p1-qj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sprout-48-bold" {...props}></Icon>
