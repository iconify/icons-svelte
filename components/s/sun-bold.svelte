<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9iqk5btj.css';
import '../../css/u/upjyccctb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9iqk5btj"/><path clip-rule="evenodd" class="upjyccctb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sun-bold" {...props}></Icon>
