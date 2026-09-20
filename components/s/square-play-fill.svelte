<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm3b-i-0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vm3b-i-0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-play-fill" {...props}></Icon>
