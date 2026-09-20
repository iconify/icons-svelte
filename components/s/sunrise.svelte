<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6vu2n_it.css';
import '../../css/q/qr2jzwbvc.css';
import '../../css/t/tajbw3b6k.css';
import '../../css/m/mmwsdobmn.css';
import '../../css/h/hfz3b8b5m.css';
import '../../css/c/c7ayd-b9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="g6vu2n_it"/><path class="qr2jzwbvc"/><path class="tajbw3b6k"/><path class="mmwsdobmn"/><path class="hfz3b8b5m"/><path class="c7ayd-b9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:sunrise" {...props}></Icon>
