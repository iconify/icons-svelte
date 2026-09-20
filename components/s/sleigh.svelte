<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/merblqb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="merblqb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sleigh" {...props}></Icon>
