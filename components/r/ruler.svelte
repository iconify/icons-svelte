<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkgyvebwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dkgyvebwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:ruler" {...props}></Icon>
