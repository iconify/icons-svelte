<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj9sbab8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aj9sbab8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:user-02" {...props}></Icon>
