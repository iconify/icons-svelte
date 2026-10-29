<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mun6vbc9f.css';
import '../../css/n/nuczxhi4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mun6vbc9f"/><path class="nuczxhi4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:square" {...props}></Icon>
