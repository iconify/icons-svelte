<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm87gbbyd.css';
import '../../css/g/gs34l4b5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jm87gbbyd"/><path class="gs34l4b5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:sun-solid" {...props}></Icon>
