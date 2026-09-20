<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drh686bei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="drh686bei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:x-p-ferd-dark" {...props}></Icon>
