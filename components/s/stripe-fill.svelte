<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a980jkb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a980jkb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:stripe-fill" {...props}></Icon>
