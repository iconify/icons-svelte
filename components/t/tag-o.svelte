<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy9noxcnw.css';
import '../../css/o/o3c_lfbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="cy9noxcnw"/><path class="o3c_lfbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:tag-o" {...props}></Icon>
