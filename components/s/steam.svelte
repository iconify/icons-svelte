<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzly_lbpi.css';
import '../../css/u/uh68dtbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzly_lbpi"/><path class="uh68dtbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:steam" {...props}></Icon>
