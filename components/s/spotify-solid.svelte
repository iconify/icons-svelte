<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_ltfhrvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="q_ltfhrvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:spotify-solid" {...props}></Icon>
