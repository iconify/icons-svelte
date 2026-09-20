<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azolitb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="azolitb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:shop" {...props}></Icon>
