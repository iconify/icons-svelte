<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqt3vmb-u.css';
import '../../css/j/jjt0fksdh.css';
import '../../css/s/spi5mob-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqt3vmb-u"/><path class="jjt0fksdh"/><path class="spi5mob-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-field-focus-bold-duotone" {...props}></Icon>
