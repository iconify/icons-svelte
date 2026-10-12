<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlx4kgb-m.css';
import '../../css/o/ogjjes7pl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlx4kgb-m"/><path class="ogjjes7pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sailboat-filled" {...props}></Icon>
