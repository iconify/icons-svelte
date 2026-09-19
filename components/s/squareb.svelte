<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7i7fkpni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="v7i7fkpni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squareb" {...props}></Icon>
