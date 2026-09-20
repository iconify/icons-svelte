<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g72s21blw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g72s21blw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:shield-2-solid" {...props}></Icon>
