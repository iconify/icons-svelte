<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr0wxdb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kr0wxdb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-division-slash-thin" {...props}></Icon>
