<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3bdu_i1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l3bdu_i1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:version-solid" {...props}></Icon>
