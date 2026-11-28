<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqm7syblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqm7syblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-root-solid" {...props}></Icon>
