<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/om11f2y7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="om11f2y7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:search-circle" {...props}></Icon>
