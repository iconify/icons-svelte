<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovw7dgidc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovw7dgidc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:uber" {...props}></Icon>
