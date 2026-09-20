<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0vsd5bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i0vsd5bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:shield-verified-fill" {...props}></Icon>
