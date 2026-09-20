<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_89b3bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e_89b3bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:scale2" {...props}></Icon>
