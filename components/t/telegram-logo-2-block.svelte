<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1_nn9ipg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s1_nn9ipg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:telegram-logo-2-block" {...props}></Icon>
