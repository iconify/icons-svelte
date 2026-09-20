<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chzbq8n6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="chzbq8n6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:vision-pro-sharp-fill" {...props}></Icon>
