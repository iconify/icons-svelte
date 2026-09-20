<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw6mmv7qp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mw6mmv7qp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:tietoevry" {...props}></Icon>
