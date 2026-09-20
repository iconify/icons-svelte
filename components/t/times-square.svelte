<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah8y2-bwd.css';
import '../../css/n/n5kd2n3_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ah8y2-bwd"/><path class="n5kd2n3_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:times-square" {...props}></Icon>
