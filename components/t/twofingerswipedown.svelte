<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhi6ye7ap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="nhi6ye7ap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:twofingerswipedown" {...props}></Icon>
