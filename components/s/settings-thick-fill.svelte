<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txd6_wbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="txd6_wbca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:settings-thick-fill" {...props}></Icon>
