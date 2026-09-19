<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtopi5btb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qtopi5btb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:unfold-more" {...props}></Icon>
