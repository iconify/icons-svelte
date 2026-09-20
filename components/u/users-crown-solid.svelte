<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3ry88brp.css';
import '../../css/a/a_iomqbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3ry88brp"/><path class="a_iomqbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:users-crown-solid" {...props}></Icon>
