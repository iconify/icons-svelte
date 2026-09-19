<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p--5p7e8l.css';
import '../../css/g/grq9qjftd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p--5p7e8l"/><path clip-rule="evenodd" class="grq9qjftd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:server-stack-16-solid" {...props}></Icon>
