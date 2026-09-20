<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcea5wauz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcea5wauz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:spreaker" {...props}></Icon>
