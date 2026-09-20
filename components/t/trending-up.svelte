<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oncx-l0yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="oncx-l0yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:trending-up" {...props}></Icon>
