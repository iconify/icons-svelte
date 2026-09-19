<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohl9o5bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":13,"height":24};
const content = `<path class="ohl9o5bts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:yandex-international" {...props}></Icon>
