<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhzur0bgo.css';
import '../../css/u/u3tdfpecc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhzur0bgo"/><path class="u3tdfpecc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:tablet-bold" {...props}></Icon>
