<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce63oobqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ce63oobqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:tree" {...props}></Icon>
