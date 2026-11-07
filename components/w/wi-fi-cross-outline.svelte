<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_vrrliit.css';
import '../../css/n/n-jx8c_mo.css';
import '../../css/p/pb5pipz8a.css';
import '../../css/q/qya8g87br.css';
import '../../css/v/v0yar7wgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_vrrliit"/><path class="n-jx8c_mo"/><path class="pb5pipz8a"/><path class="qya8g87br"/><path class="v0yar7wgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wi-fi-cross-outline" {...props}></Icon>
