<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwvuisbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwvuisbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:south-west-duotone" {...props}></Icon>
