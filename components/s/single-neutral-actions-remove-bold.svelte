<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trxr8zl8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trxr8zl8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:single-neutral-actions-remove-bold" {...props}></Icon>
