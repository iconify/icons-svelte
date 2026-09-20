<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj2bkrcmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vj2bkrcmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:verified-check-outline" {...props}></Icon>
