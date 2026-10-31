<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzumm9f2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzumm9f2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:taxi-gloss" {...props}></Icon>
