<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbfmuwa3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cbfmuwa3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-up-left-fill" {...props}></Icon>
