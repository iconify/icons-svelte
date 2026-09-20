<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao96m-b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ao96m-b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:some-embed" {...props}></Icon>
