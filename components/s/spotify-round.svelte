<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziucbk6ga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ziucbk6ga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:spotify-round" {...props}></Icon>
