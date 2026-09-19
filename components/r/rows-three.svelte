<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/annt9abeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="annt9abeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:rows-three" {...props}></Icon>
