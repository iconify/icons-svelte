<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe20_kbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xe20_kbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:sqlite" {...props}></Icon>
