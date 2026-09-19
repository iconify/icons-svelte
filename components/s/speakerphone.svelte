<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6v5jeb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="t6v5jeb-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:speakerphone" {...props}></Icon>
