<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcxv81l_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jcxv81l_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-division-square-fill" {...props}></Icon>
