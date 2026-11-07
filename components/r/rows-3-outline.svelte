<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhtilt0dn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qhtilt0dn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rows-3-outline" {...props}></Icon>
