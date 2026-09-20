<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uypib39ja.css';
import '../../css/i/imes1f47p.css';
import '../../css/n/nh26eqbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="uypib39ja"><path class="imes1f47p"/><path class="nh26eqbdu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:solidity" {...props}></Icon>
