<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izn2dcbwr.css';
import '../../css/a/au2mywbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izn2dcbwr"/><path class="au2mywbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:router-signal-bold" {...props}></Icon>
