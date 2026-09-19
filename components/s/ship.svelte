<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k150ojlno.css';
import '../../css/o/ol2nzbc1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":24};
const content = `<path class="k150ojlno"/><path class="ol2nzbc1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:ship" {...props}></Icon>
