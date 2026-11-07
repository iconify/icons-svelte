<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffu3be33e.css';
import '../../css/e/e91nqrblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffu3be33e"/><path clip-rule="evenodd" class="e91nqrblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-field-outline" {...props}></Icon>
