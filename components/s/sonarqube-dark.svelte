<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0_mkcckb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g0_mkcckb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sonarqube-dark" {...props}></Icon>
