<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itw7y3bch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itw7y3bch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:triangle-gloss" {...props}></Icon>
