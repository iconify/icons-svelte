<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bszvb5wjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bszvb5wjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:stellar-logo-block" {...props}></Icon>
