<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdzk9tywb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdzk9tywb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:undo" {...props}></Icon>
