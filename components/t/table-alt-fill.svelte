<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnl2zkb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnl2zkb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:table-alt-fill" {...props}></Icon>
