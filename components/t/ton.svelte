<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loq-8obfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="loq-8obfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ton" {...props}></Icon>
