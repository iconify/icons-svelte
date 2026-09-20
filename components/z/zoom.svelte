<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0d1hcbit.css';
import '../../css/u/u2n18rsfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q0d1hcbit"/><path class="u2n18rsfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zoom" {...props}></Icon>
