<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h93zme_zu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h93zme_zu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:traffic-barrier-filled" {...props}></Icon>
