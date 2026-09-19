<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfz3w9lrl.css';
import '../../css/i/iq03fbgcg.css';
import '../../css/t/tzwzvh3jp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="yfz3w9lrl"/><path class="iq03fbgcg"/><path class="tzwzvh3jp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:street-view" {...props}></Icon>
