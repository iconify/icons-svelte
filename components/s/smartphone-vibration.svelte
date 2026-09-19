<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng5_5oycj.css';
import '../../css/p/pt5wbdc-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer ng5_5oycj"/><path class="duoicon-primary-layer pt5wbdc-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:smartphone-vibration" {...props}></Icon>
