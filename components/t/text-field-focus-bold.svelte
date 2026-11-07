<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2d8zobch.css';
import '../../css/u/urrp9ssxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2d8zobch"/><path clip-rule="evenodd" class="urrp9ssxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-field-focus-bold" {...props}></Icon>
