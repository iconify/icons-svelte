<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abwvd3b5g.css';
import '../../css/t/t7eub0bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abwvd3b5g"/><path class="t7eub0bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vanio" {...props}></Icon>
