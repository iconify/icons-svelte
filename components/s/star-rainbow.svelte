<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chprfjb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="chprfjb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:star-rainbow" {...props}></Icon>
