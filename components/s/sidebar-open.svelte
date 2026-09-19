<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlnbmiavn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jlnbmiavn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:sidebar-open" {...props}></Icon>
