<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze80w9uou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ze80w9uou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:structure-outline" {...props}></Icon>
