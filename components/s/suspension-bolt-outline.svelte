<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sexa44bni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sexa44bni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:suspension-bolt-outline" {...props}></Icon>
