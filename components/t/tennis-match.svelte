<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8zxj3bty.css';
import '../../css/m/mg2yoibod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8zxj3bty"/><path class="mg2yoibod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:tennis-match" {...props}></Icon>
