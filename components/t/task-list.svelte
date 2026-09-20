<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifyzdyjkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="ifyzdyjkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:task-list" {...props}></Icon>
