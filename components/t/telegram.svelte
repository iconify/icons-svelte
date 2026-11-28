<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/ggubv6whl.css';
import '../../css/s/sk3qebj-f.css';
import '../../css/o/oet5zxb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ggubv6whl"/><path class="sk3qebj-f"/><path class="oet5zxb6o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:telegram" {...props}></Icon>
