<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyc_ozb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyc_ozb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:space-sharp-duotone" {...props}></Icon>
