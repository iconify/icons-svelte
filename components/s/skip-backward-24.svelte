<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_e_ded7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_e_ded7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:skip-backward-24" {...props}></Icon>
