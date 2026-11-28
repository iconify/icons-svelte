<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zac9grbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zac9grbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sun-dim-solid" {...props}></Icon>
