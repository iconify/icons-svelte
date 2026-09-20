<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah2klsbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ah2klsbvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:setting4" {...props}></Icon>
