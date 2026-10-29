<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h83a2chhh.css';
import '../../css/o/oncz_d6_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h83a2chhh"/><path class="oncz_d6_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:tag" {...props}></Icon>
