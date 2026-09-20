<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6n_93bla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6n_93bla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:transfer-long-right-light" {...props}></Icon>
