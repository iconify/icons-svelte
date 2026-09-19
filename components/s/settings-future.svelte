<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/v/vtf1hxb3i.css';
import '../../css/f/fkdpf6eac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vtf1hxb3i"/><path class="fkdpf6eac"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:settings-future" {...props}></Icon>
