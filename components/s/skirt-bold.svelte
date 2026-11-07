<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zppc8rbit.css';
import '../../css/f/fmy-1sbhx.css';
import '../../css/o/otzgm8e6s.css';
import '../../css/c/c4oqwbcar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zppc8rbit"/><path class="fmy-1sbhx"/><path class="otzgm8e6s"/><path class="c4oqwbcar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:skirt-bold" {...props}></Icon>
