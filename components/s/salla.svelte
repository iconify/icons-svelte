<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9fh50bdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9fh50bdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:salla" {...props}></Icon>
