<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7e8phbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y7e8phbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:tennis" {...props}></Icon>
