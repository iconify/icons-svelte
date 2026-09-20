<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob_fhebgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ob_fhebgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-underline-circle-bold" {...props}></Icon>
