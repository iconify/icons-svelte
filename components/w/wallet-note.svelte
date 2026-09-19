<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjccsx91c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjccsx91c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wallet-note" {...props}></Icon>
